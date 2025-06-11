/ App.jsx import { useEffect } from "react"; import { motion } from "framer-motion"; import { Button } from "@/components/ui/button"; import { Phone, MapPin } from "lucide-react";

const appliances = [ { title: "Washer & Dryer", img: "/images/washer-dryer.jpg", desc: "Fast repair of washing machines and dryers." }, { title: "Dishwasher", img: "/images/dishwasher.jpg", desc: "Fix leaks, no cleaning, and draining issues." }, { title: "Refrigerator", img: "/images/refrigerator.jpg", desc: "Cooling problems, ice maker repairs, and more." }, { title: "Microwave", img: "/images/microwave.jpg", desc: "We handle no heating, sparking, and more." }, { title: "Oven", img: "/images/oven.jpg", desc: "Accurate temperature repairs and more." }, { title: "Stove", img: "/images/stove.jpg", desc: "Ignition issues, broken burners, and more." } ];

export default function App() { useEffect(() => { document.title = "Pacific Repair Solutions – Appliance Repair Sacramento"; }, []);

return (
